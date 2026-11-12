<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7z1-odpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p7z1-odpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dockge-light" /></template>

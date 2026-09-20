<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsi_di3ke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hsi_di3ke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dockpeek-light" /></template>

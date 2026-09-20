<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3e7nvr4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m3e7nvr4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mafl-light" /></template>

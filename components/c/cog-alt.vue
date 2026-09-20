<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/y/ynqmrvbmv.css';
import '../../css/o/ou-f-vnmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="gp_8x1bzb"><path class="ynqmrvbmv"/><path class="ou-f-vnmu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:cog-alt" /></template>

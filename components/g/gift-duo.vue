<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pv-vycm8e.css';
import '../../css/d/dpjsdlepr.css';
import '../../css/t/tntq76sxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="pv-vycm8e"/><path class="dpjsdlepr"/><path class="tntq76sxu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:gift-duo" /></template>

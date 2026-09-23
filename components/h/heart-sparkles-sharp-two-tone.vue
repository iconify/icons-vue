<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/z/zwd3a68ww.css';
import '../../css/q/qz4hw_hri.css';
import '../../css/h/h2gye8b5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="zwd3a68ww"/><path class="qz4hw_hri"/><path class="h2gye8b5v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:heart-sparkles-sharp-two-tone" /></template>

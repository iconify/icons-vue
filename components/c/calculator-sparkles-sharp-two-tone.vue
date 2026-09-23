<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/d/dj04zfbhi.css';
import '../../css/j/j8doxx_bn.css';
import '../../css/i/i645x0uvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="dj04zfbhi"/><path class="j8doxx_bn"/><path class="i645x0uvs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:calculator-sparkles-sharp-two-tone" /></template>

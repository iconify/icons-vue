<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/m/mutq2p_rd.css';
import '../../css/o/o6099mb7z.css';
import '../../css/f/fi8fabbiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="mutq2p_rd"/><path class="o6099mb7z"/><path class="fi8fabbiq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flask-conical-off-sharp-two-tone" /></template>

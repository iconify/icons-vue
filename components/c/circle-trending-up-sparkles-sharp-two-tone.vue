<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/i/im8wmac8f.css';
import '../../css/z/zr5m9kbwl.css';
import '../../css/z/z3w9o1b2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="im8wmac8f"/><path class="zr5m9kbwl"/><path class="z3w9o1b2x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-trending-up-sparkles-sharp-two-tone" /></template>

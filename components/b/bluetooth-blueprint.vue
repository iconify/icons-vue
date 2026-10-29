<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/h/hngrqwb5t.css';
import '../../css/f/fcyg8zbdc.css';
import '../../css/o/o3ggb2czz.css';
import '../../css/m/mwcb5wb9h.css';
import '../../css/s/saxk-lbfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="hngrqwb5t wm-deco"/><path class="fcyg8zbdc wm-deco"/><path class="o3ggb2czz wm-deco"/><path class="mwcb5wb9h"/><path class="saxk-lbfy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bluetooth-blueprint" /></template>

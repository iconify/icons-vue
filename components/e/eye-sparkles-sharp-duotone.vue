<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/j/j7-oa0fhr.css';
import '../../css/c/c6upwkbge.css';
import '../../css/s/sjzx1lb1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="j7-oa0fhr"/><path class="c6upwkbge"/><path class="sjzx1lb1f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:eye-sparkles-sharp-duotone" /></template>

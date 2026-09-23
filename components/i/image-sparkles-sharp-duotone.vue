<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/q/q_5ckyazc.css';
import '../../css/j/jt285nhnx.css';
import '../../css/l/lgzrwwbeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="q_5ckyazc"/><path class="jt285nhnx"/><path class="lgzrwwbeq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:image-sparkles-sharp-duotone" /></template>

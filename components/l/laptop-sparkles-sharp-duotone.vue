<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/v/v045ocb8q.css';
import '../../css/c/c6upwkbge.css';
import '../../css/j/j6wq2e0hx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="v045ocb8q"/><path class="c6upwkbge"/><path class="j6wq2e0hx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:laptop-sparkles-sharp-duotone" /></template>

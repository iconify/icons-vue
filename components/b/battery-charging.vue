<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/u/ux_jcbb_g.css';
import '../../css/h/h7ix5eoar.css';
import '../../css/h/hnr4r-ben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ux_jcbb_g"/><path class="h7ix5eoar"/><path class="hnr4r-ben"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="evicons:battery-charging" /></template>

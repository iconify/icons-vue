<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/r/r4s1crbcx.css';
import '../../css/k/krgk-cb_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect transform="rotate(90 12 6.667)" class="r4s1crbcx"/><rect transform="rotate(90 8 17.333)" class="krgk-cb_q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:align-3-left" /></template>

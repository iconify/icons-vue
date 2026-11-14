<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/q/q4lcrg_oy.css';
import '../../css/q/q22fozbrr.css';
import '../../css/r/rgm89rb0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="q4lcrg_oy"/><path class="q22fozbrr"/><path class="rgm89rb0x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="evicons:accessible-charging" /></template>

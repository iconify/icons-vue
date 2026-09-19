<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/x/xgco95bzv.css';
import '../../css/m/mt1-zg82v.css';
import '../../css/c/c-q4twgtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xgco95bzv"/><path class="mt1-zg82v"/><path class="c-q4twgtg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-auto-rotate" /></template>

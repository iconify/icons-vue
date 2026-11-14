<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/l/lgvsbdbea.css';
import '../../css/k/k1dc_j0wb.css';
import '../../css/y/yw-1u0bgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lgvsbdbea"/><path class="k1dc_j0wb"/><path class="yw-1u0bgb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-brain-04" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5mxzlskq.css';
import '../../css/j/jgw_zob1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i5mxzlskq"/><path class="jgw_zob1f ouiIcon__fillSecondary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:app-monitoring" /></template>

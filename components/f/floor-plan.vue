<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/l/l2iew4b8d.css';
import '../../css/h/hcev0sb5i.css';
import '../../css/j/j7v6lsk2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="l2iew4b8d"/><path class="hcev0sb5i"/><path class="j7v6lsk2x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:floor-plan" /></template>

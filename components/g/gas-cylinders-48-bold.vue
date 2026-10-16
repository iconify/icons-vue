<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihmii9b0s.css';
import '../../css/d/d1uvu5qok.css';
import '../../css/p/p7ykb5bhn.css';
import '../../css/h/h7u592kmh.css';
import '../../css/i/imgtsabmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ihmii9b0s"/><path class="d1uvu5qok"/><path class="p7ykb5bhn"/><path class="h7u592kmh"/><path class="imgtsabmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gas-cylinders-48-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfo2a7bug.css';
import '../../css/x/xnnzndbop.css';
import '../../css/h/hemw72bsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rfo2a7bug"/><path class="xnnzndbop"/><path class="hemw72bsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:invoice" /></template>

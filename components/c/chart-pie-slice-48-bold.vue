<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crxzhebgb.css';
import '../../css/r/rpsqcp5fk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="crxzhebgb"/><path class="rpsqcp5fk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-pie-slice-48-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dj2y6_b-x.css';
import '../../css/b/bew7-otna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dj2y6_b-x"/><path class="bew7-otna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:carbon-budget-48" /></template>

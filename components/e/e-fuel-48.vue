<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpxa9ub0u.css';
import '../../css/b/bwb32mb4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rpxa9ub0u"/><path class="bwb32mb4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:e-fuel-48" /></template>

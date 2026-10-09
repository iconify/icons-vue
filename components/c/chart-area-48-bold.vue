<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8ue7ubrb.css';
import '../../css/x/x-vy4em_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l8ue7ubrb"/><path class="x-vy4em_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-area-48-bold" /></template>

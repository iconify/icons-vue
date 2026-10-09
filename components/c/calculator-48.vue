<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6wl1rbzv.css';
import '../../css/p/p5fo1bbqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k6wl1rbzv"/><path class="p5fo1bbqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:calculator-48" /></template>

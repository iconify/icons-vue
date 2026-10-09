<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1w0d8d4j.css';
import '../../css/i/i0y7ncbnv.css';
import '../../css/f/f54j4-b-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p1w0d8d4j"/><path class="i0y7ncbnv"/><path class="f54j4-b-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:building-check-48" /></template>

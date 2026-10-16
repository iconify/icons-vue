<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9ilzsbir.css';
import '../../css/y/y2aittblo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v9ilzsbir"/><path class="y2aittblo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:level-gauge-48-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlyerkbto.css';
import '../../css/u/u0bew_y1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vlyerkbto"/><path class="u0bew_y1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:carbon-negative-48-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3bwoucvq.css';
import '../../css/t/tydgjvody.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q3bwoucvq"/><path class="tydgjvody"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:candle-48-bold" /></template>

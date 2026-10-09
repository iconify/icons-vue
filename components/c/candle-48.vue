<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvshp_bta.css';
import '../../css/a/a1o2reb9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jvshp_bta"/><path class="a1o2reb9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:candle-48" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6t6ne13x.css';
import '../../css/v/vjvtfabym.css';
import '../../css/v/vpb3bu46w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j6t6ne13x"/><path class="vjvtfabym"/><path class="vpb3bu46w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ammonia-tank-48-bold" /></template>

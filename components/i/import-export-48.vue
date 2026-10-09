<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di7upcblc.css';
import '../../css/o/o5gtl8zhh.css';
import '../../css/w/we-nd7j-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="di7upcblc"/><path class="o5gtl8zhh"/><path class="we-nd7j-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:import-export-48" /></template>

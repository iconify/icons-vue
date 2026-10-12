<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inizydo0z.css';
import '../../css/q/qy7v0ra7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="inizydo0z"/><path class="qy7v0ra7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:drawing-compass-48" /></template>

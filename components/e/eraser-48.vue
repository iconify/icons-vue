<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcwtdzb8g.css';
import '../../css/r/r8vpsobrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xcwtdzb8g"/><path class="r8vpsobrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:eraser-48" /></template>

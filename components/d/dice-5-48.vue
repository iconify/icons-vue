<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lr7h2fb6d.css';
import '../../css/e/e7dtu3-ol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lr7h2fb6d"/><path class="e7dtu3-ol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dice-5-48" /></template>

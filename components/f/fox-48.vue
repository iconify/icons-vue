<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8o7jbnvk.css';
import '../../css/x/x0f0yioou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s8o7jbnvk"/><path class="x0f0yioou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fox-48" /></template>

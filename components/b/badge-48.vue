<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k50n0vbya.css';
import '../../css/e/ei8ys-9zj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k50n0vbya"/><path class="ei8ys-9zj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:badge-48" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sq_9-8b5f.css';
import '../../css/d/dfsy1hrxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sq_9-8b5f"/><path class="dfsy1hrxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-network-48" /></template>

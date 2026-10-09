<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5sdatbxs.css';
import '../../css/e/e0qbytbil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k5sdatbxs"/><path class="e0qbytbil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ice-cream-48" /></template>

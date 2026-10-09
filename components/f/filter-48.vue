<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkwqbs4aq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pkwqbs4aq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:filter-48" /></template>

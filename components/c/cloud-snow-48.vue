<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze5c6ablq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ze5c6ablq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-snow-48" /></template>

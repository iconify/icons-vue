<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e77v1eb-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="e77v1eb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:low-bars2x-outline" /></template>

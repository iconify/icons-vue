<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aogr9_c5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="aogr9_c5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:heart-rate-pulse-graph-remix" /></template>

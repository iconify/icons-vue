<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9l2qqe6j.css';
import '../../css/c/cy1drpb6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n9l2qqe6j"/><path class="cy1drpb6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-bar-grouped-48" /></template>

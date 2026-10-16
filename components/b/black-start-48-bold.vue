<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4b25kb_a.css';
import '../../css/e/ep5y64b3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k4b25kb_a"/><path class="ep5y64b3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:black-start-48-bold" /></template>

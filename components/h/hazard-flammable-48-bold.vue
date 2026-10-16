<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2mjsubix.css';
import '../../css/u/ub9hmvbkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h2mjsubix"/><path class="ub9hmvbkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hazard-flammable-48-bold" /></template>

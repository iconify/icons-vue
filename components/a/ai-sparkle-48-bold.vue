<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3uo2ubmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z3uo2ubmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ai-sparkle-48-bold" /></template>

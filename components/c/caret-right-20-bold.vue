<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ws7p95bcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ws7p95bcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:caret-right-20-bold" /></template>

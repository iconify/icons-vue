<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9czz4bal.css';
import '../../css/l/laagh_b7q.css';
import '../../css/q/q1ee2b8fe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d9czz4bal"/><path class="laagh_b7q"/><path class="q1ee2b8fe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-plug-48" /></template>

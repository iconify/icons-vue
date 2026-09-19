<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7-k3vx_v.css';
import '../../css/i/i-hdiybge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p7-k3vx_v"/><path class="i-hdiybge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:drill-through" /></template>

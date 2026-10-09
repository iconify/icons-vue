<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ll4p3cbte.css';
import '../../css/m/m4t5o-y0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ll4p3cbte"/><path class="m4t5o-y0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:e-fuel-20-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/maxs7mbxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="maxs7mbxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:capture" /></template>

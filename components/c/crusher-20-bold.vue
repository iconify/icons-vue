<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1bs-ybvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j1bs-ybvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crusher-20-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dx_6a7bpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dx_6a7bpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hail-20-bold" /></template>

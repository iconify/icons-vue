<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg_d3jumz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cg_d3jumz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:firecracker-line" /></template>

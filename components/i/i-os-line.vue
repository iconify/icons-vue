<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tt-tfom0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tt-tfom0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:i-os-line" /></template>

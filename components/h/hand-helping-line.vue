<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjp3xsbsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjp3xsbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hand-helping-line" /></template>

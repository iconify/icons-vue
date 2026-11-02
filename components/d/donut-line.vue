<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i33guhbcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i33guhbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:donut-line" /></template>

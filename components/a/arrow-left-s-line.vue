<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub97n3bpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ub97n3bpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-left-s-line" /></template>

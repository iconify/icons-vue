<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-lm-kbpu.css';
import '../../css/k/k4cp8nxvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h-lm-kbpu"/><path class="k4cp8nxvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:machine-learning" /></template>

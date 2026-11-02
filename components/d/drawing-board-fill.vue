<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jppu-ub8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jppu-ub8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:drawing-board-fill" /></template>

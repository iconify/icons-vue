<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_rx8b45j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_rx8b45j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:file-text-star" /></template>

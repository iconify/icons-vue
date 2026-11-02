<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sd41p8x-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sd41p8x-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chess-rook-fill" /></template>

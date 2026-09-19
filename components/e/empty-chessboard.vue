<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr2fz_s7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jr2fz_s7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:empty-chessboard" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpu92h-yo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fpu92h-yo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chess-pawn-solid" /></template>

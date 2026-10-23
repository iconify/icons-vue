<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9ubeclce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t9ubeclce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:chess-pawn" /></template>

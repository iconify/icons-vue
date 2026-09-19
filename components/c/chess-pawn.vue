<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhy94o1ju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhy94o1ju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:chess-pawn" /></template>

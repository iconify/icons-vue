<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ua2mlxb5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ua2mlxb5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:chess-pawn" /></template>

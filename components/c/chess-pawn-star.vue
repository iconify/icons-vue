<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inykoi9lh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="inykoi9lh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:chess-pawn-star" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynd4v0btj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ynd4v0btj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:chess-pawn" /></template>

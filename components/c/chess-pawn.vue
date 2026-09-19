<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_59zsbpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="t_59zsbpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:chess-pawn" /></template>

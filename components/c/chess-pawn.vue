<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cm31a9pfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="cm31a9pfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:chess-pawn" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvguc5buz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bvguc5buz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:card-game-symbols" /></template>

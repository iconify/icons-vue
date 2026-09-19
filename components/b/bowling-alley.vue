<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmd94dbut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cmd94dbut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bowling-alley" /></template>

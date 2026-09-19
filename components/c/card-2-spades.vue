<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uy954vbun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uy954vbun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-2-spades" /></template>

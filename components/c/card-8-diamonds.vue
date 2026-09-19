<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rs1on-byn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rs1on-byn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-8-diamonds" /></template>

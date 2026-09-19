<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c42aj1b_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c42aj1b_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hammer-break" /></template>

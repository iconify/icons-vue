<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyhzqe_tg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cyhzqe_tg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-052" /></template>

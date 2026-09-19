<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egbi063qu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="egbi063qu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:jawless-cyclop" /></template>

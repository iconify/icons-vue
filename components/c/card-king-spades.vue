<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9csp_4qz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m9csp_4qz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-king-spades" /></template>

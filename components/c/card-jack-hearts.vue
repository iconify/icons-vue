<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyjtk83dk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eyjtk83dk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-jack-hearts" /></template>

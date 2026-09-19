<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyfb7gbzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iyfb7gbzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:love-letter" /></template>

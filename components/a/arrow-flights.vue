<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5t4rgbxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f5t4rgbxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:arrow-flights" /></template>

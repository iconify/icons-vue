<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1cny5eir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i1cny5eir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:coinflip" /></template>

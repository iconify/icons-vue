<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mky1-gb8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mky1-gb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-8-spades" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isq8ce6ad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="isq8ce6ad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:daemon-skull" /></template>

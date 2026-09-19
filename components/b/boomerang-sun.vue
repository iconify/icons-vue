<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlby0xbcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vlby0xbcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:boomerang-sun" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihepocela.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ihepocela"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:boss-key" /></template>

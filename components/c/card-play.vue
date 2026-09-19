<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ermx9q4nx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ermx9q4nx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-play" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jq1nyqbpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jq1nyqbpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hamburger" /></template>

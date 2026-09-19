<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c51pwqbgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c51pwqbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:expand" /></template>

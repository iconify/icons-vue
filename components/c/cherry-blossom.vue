<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w29npqbft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w29npqbft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:cherry-blossom" /></template>

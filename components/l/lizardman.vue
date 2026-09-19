<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzv2y_5jn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fzv2y_5jn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:lizardman" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp7iw6bnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cp7iw6bnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:lead-pipe" /></template>

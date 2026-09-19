<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9a2xk5uq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m9a2xk5uq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cricket-bat" /></template>

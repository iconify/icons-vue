<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzod3abgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qzod3abgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-jack-diamonds" /></template>

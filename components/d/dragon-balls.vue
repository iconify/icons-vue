<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n02019byg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n02019byg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dragon-balls" /></template>

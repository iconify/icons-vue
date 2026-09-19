<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hefd2s-6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hefd2s-6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-queen-diamonds" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kei78h1bh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kei78h1bh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:baby-face" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gq4h58boj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gq4h58boj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:heart-earrings" /></template>

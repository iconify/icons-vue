<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1kq5qb0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y1kq5qb0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cursed-star" /></template>

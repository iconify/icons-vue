<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogvd8x0ke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ogvd8x0ke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:blackball" /></template>

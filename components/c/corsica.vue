<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ym8kz_1yf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ym8kz_1yf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:corsica" /></template>

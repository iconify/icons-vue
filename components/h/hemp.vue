<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwkm-sb4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rwkm-sb4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hemp" /></template>

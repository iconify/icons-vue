<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ka--vfbtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ka--vfbtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:electrical-socket" /></template>

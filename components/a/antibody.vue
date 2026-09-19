<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk2c879cp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vk2c879cp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:antibody" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvy7ldnxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uvy7ldnxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:focused-lightning" /></template>

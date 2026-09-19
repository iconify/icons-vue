<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5s7xqbcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k5s7xqbcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cctv-camera" /></template>

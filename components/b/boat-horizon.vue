<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhx1p9phh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dhx1p9phh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:boat-horizon" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1j98kb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m1j98kb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:disc-golf-basket" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ups-hk70t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ups-hk70t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-jack-clubs" /></template>

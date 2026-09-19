<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rg0_v2f9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rg0_v2f9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:crab-claw" /></template>

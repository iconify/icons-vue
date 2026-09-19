<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwrr1-btw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fwrr1-btw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:forward-sun" /></template>

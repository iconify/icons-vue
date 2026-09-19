<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7nvg8bps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a7nvg8bps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bamboo-fountain" /></template>

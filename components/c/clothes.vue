<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ji-4rabzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ji-4rabzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:clothes" /></template>

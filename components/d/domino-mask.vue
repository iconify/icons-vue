<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulw37cbuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ulw37cbuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:domino-mask" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjz47zb1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rjz47zb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:full-wood-bucket" /></template>

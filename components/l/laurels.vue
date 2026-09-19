<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2dggi7_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k2dggi7_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:laurels" /></template>

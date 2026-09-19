<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmt4rvbrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mmt4rvbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dinosaur-bones" /></template>

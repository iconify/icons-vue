<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d24qi6xmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d24qi6xmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:entangled-typhoon" /></template>

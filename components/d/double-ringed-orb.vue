<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pe5m685gm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pe5m685gm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:double-ringed-orb" /></template>

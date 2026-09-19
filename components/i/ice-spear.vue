<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqge1p_bt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iqge1p_bt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ice-spear" /></template>

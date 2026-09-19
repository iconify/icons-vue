<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pclguk7kg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pclguk7kg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:indian-palace" /></template>

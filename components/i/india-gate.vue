<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xf--k1b3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xf--k1b3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:india-gate" /></template>

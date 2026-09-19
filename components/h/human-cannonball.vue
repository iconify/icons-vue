<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyr4txpno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tyr4txpno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:human-cannonball" /></template>

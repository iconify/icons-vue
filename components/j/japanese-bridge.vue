<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8r4hyltc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d8r4hyltc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:japanese-bridge" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkebvnbcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hkebvnbcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:extra-time" /></template>

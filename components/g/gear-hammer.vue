<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgd8_wbyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dgd8_wbyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:gear-hammer" /></template>

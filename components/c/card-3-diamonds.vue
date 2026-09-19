<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov4q4xpyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ov4q4xpyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-3-diamonds" /></template>

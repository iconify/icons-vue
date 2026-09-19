<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uywcv-61a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uywcv-61a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:amplitude" /></template>

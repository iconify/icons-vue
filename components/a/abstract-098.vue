<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfv_i_5tw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hfv_i_5tw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-098" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw1-d_wqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nw1-d_wqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:golf-tee" /></template>

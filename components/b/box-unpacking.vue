<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbr-uubfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hbr-uubfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:box-unpacking" /></template>

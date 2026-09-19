<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw9ye5pbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zw9ye5pbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bowling-pin" /></template>

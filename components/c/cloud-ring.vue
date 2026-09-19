<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zx1wkccur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zx1wkccur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cloud-ring" /></template>

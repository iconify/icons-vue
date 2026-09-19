<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjzynwbkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jjzynwbkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:horizon-road" /></template>

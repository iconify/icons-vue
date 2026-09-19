<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_d9ekbof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z_d9ekbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:crystal-shrine" /></template>

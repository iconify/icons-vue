<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjee6g_jl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qjee6g_jl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:beer-horn" /></template>

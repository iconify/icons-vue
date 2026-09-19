<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jddsx1v0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jddsx1v0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:arm" /></template>

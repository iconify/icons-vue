<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw62wh_1x.css';
import '../../css/p/poade0yht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gw62wh_1x"/><path class="poade0yht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:dock-filled" /></template>

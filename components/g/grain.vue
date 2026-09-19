<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/horf_2btv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="horf_2btv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:grain" /></template>

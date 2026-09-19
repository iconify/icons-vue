<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3tga9bvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d3tga9bvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:interleaved-claws" /></template>

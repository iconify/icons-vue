<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzgn6nyji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pzgn6nyji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hot-surface" /></template>

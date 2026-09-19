<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2ydl-l0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2ydl-l0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:home-alt" /></template>

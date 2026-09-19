<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9hxqcc5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f9hxqcc5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:earth-spit" /></template>

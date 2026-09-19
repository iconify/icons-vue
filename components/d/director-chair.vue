<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-wdxybns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z-wdxybns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:director-chair" /></template>

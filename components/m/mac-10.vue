<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z735ileap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z735ileap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:mac-10" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pktnifbwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="pktnifbwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:dollar-sign-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5hobibwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="i5hobibwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:lighthouse-14" /></template>

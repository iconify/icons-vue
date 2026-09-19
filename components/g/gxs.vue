<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffh0fmbeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ffh0fmbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:gxs" /></template>

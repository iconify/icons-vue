<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fft62cnys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fft62cnys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hand-coins-line" /></template>

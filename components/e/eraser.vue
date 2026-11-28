<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kh2wpkbqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kh2wpkbqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:eraser" /></template>

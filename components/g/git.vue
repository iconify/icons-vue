<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fft4c3dqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fft4c3dqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:git" /></template>

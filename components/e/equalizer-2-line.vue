<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-j23qbsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-j23qbsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:equalizer-2-line" /></template>

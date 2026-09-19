<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psx3-w2jj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="psx3-w2jj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-left-arrow-alt" /></template>

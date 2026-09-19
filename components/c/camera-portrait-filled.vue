<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm6zd0yms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lm6zd0yms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:camera-portrait-filled" /></template>

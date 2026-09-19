<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu5vlxh4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vu5vlxh4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:donate-heart-filled" /></template>

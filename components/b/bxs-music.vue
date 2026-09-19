<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw4l3nbae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zw4l3nbae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-music" /></template>

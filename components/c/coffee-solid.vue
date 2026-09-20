<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxkghox2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hxkghox2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:coffee-solid" /></template>

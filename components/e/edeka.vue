<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd78jgbrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hd78jgbrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:edeka" /></template>

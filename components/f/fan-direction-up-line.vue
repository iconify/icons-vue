<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/haqr67bmp.css';
import '../../css/i/iixqn4bev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="haqr67bmp"/><path class="iixqn4bev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fan-direction-up-line" /></template>

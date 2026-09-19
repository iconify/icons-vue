<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mq6e7rs9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mq6e7rs9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:diamond" /></template>

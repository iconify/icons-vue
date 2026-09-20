<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hao-mcclc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hao-mcclc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:battery-low-line" /></template>

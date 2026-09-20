<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhwhtybel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zhwhtybel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:funds-box-line" /></template>

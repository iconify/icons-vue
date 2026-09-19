<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwn5_d3cv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwn5_d3cv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:a-arrow-up" /></template>

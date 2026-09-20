<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipk0zxblz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ipk0zxblz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:home-7-fill" /></template>

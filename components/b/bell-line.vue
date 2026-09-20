<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3-8ftyow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3-8ftyow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:bell-line" /></template>

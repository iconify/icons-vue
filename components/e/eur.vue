<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te9g8x_4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1408};
const content = `<path class="te9g8x_4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:eur" /></template>

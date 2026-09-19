<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/riq60ynai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="riq60ynai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:arrow-up-left" /></template>

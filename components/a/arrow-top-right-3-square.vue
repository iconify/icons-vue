<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ig5nnwytm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ig5nnwytm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-top-right-3-square" /></template>

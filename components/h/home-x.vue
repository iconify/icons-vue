<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-5kho9ad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-5kho9ad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:home-x" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrq3bhfat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrq3bhfat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:brand-twitter" /></template>

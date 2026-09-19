<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tou30pmzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tou30pmzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:long-arrow-right-up-1" /></template>

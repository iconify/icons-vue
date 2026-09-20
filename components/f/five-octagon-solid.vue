<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmwjm1alm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmwjm1alm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:five-octagon-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xexyiyqee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xexyiyqee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bike-fill" /></template>

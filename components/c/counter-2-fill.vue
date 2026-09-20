<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zeusycbhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zeusycbhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:counter-2-fill" /></template>

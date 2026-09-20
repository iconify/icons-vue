<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igin2l9yo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="igin2l9yo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ad-circle-line" /></template>

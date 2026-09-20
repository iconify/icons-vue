<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uin8x9ouj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uin8x9ouj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:laugh-line" /></template>

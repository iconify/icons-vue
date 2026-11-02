<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1x3l2bav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1x3l2bav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:beard-line" /></template>

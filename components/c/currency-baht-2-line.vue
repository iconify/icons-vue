<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjya9dbzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjya9dbzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-baht-2-line" /></template>

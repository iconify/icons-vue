<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu72-xdxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gu72-xdxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:alipay-fill" /></template>

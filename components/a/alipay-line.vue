<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbp4lhrjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbp4lhrjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:alipay-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe3x9j2kq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xe3x9j2kq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:alipay-line" /></template>

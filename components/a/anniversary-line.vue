<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zf--3zurr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zf--3zurr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:anniversary-line" /></template>

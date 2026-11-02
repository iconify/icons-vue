<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qibd9rb1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qibd9rb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:box-4-line" /></template>

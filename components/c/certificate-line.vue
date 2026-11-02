<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqj3jzpsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqj3jzpsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:certificate-line" /></template>

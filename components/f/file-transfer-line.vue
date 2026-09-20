<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znnwz6jyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="znnwz6jyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-transfer-line" /></template>

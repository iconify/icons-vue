<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh5u8_bkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zh5u8_bkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-output-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewru3_btl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ewru3_btl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:gesture-typing-filled" /></template>

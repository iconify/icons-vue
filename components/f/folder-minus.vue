<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn88f4bao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="xn88f4bao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:folder-minus" /></template>

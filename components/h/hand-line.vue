<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh3c-abpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zh3c-abpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:hand-line" /></template>

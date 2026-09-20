<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsqmarbtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsqmarbtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:add2-filled" /></template>

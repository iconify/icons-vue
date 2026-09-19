<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/av_80kbba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="av_80kbba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:bcd" /></template>

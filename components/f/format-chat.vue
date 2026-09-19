<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n--glj5wx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n--glj5wx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:format-chat" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn32-xxqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xn32-xxqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:email-filled" /></template>

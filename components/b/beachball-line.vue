<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxzv38bcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxzv38bcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:beachball-line" /></template>

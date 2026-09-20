<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqsqo9bze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqsqo9bze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:bell-plus" /></template>

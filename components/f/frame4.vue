<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xk8z51b7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xk8z51b7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:frame4" /></template>

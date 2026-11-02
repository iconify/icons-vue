<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te6448bsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="te6448bsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:camcorder-3-fill" /></template>

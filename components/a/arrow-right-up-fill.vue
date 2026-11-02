<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_-65y1bj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_-65y1bj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-right-up-fill" /></template>

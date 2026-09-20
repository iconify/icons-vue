<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kr8y-6-3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kr8y-6-3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:donut-fill" /></template>

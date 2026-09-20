<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymw3uvdzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymw3uvdzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bilibili-fill" /></template>

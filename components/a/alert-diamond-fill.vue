<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evn9cubmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evn9cubmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:alert-diamond-fill" /></template>

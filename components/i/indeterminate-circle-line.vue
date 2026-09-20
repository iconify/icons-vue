<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wzd098bqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wzd098bqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:indeterminate-circle-line" /></template>

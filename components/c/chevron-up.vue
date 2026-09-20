<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qidi1vbhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="qidi1vbhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:chevron-up" /></template>

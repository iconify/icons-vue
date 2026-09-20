<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/veevc8lbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="veevc8lbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-arrow-down-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j661y24zt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j661y24zt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-marked-line" /></template>

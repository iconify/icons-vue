<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5o9ygl0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5o9ygl0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-rupee-line" /></template>

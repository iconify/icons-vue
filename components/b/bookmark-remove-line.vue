<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8k5alboq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8k5alboq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bookmark-remove-line" /></template>

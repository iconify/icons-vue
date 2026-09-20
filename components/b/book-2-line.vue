<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8gtwgbcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j8gtwgbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-2-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmjxt8bcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmjxt8bcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-more-fill" /></template>

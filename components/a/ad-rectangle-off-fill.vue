<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9kaqqbfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9kaqqbfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ad-rectangle-off-fill" /></template>

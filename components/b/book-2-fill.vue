<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7wbhg_wb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h7wbhg_wb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-2-fill" /></template>

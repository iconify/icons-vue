<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7xhyxb7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7xhyxb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-open-text-fill" /></template>

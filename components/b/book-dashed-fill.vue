<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1-j_2mkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e1-j_2mkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-dashed-fill" /></template>

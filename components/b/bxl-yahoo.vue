<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3i547bbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3i547bbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-yahoo" /></template>

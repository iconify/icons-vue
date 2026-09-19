<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqz_8mb_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jqz_8mb_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:history" /></template>

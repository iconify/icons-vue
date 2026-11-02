<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi7_ttbiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fi7_ttbiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:badge-plus-fill" /></template>

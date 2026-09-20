<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syoc4d6_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="syoc4d6_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-baht-2-line" /></template>

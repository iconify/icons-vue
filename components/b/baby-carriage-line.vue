<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ton41i5am.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ton41i5am"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:baby-carriage-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z39dw-vma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z39dw-vma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-baht-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvlr7taap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvlr7taap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:car-2-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tos4f_s-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tos4f_s-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:arrow-triangle-loop" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpu8nbc8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpu8nbc8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-d" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlsefonkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xlsefonkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:corner-down-right" /></template>

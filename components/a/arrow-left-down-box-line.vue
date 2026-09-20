<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdh5gcb3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdh5gcb3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-left-down-box-line" /></template>

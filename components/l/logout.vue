<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eek0nq2yo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eek0nq2yo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:logout" /></template>

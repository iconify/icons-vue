<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m112204ku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m112204ku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-right-down-long-fill" /></template>

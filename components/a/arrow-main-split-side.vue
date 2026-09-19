<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t05-ilkfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t05-ilkfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:arrow-main-split-side" /></template>

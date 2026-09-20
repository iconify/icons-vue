<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erp53acgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="erp53acgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:article-redirect-ltr" /></template>

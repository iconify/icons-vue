<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjki1ptty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zjki1ptty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:italic-c" /></template>

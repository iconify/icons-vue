<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhdqeq3jz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fhdqeq3jz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:list-numbered-rtl" /></template>

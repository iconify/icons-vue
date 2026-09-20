<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jiycsjpug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jiycsjpug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:list-bullet-ltr" /></template>

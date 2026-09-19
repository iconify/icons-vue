<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydjm23-rr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ydjm23-rr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:chess-bishop" /></template>

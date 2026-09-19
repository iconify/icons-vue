<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yuew33vie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="yuew33vie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:heart" /></template>

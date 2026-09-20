<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqwqqcbgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sqwqqcbgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:battery-full" /></template>

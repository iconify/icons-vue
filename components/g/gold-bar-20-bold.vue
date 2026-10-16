<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yoqkmxbwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yoqkmxbwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gold-bar-20-bold" /></template>

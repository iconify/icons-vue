<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv8a032vk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zv8a032vk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:jump-over-16" /></template>

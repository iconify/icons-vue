<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybmao4abp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ybmao4abp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:boxes-packing" /></template>

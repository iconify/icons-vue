<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0r6koz6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="r0r6koz6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:calendar" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3zqhx3gb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l3zqhx3gb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:expand" /></template>

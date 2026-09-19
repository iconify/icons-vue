<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9utgva7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a9utgva7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:ant" /></template>

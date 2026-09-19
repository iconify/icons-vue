<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z58ye-npm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="z58ye-npm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:laptop-outlined" /></template>

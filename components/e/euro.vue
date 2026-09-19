<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx1mdubiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="sx1mdubiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:euro" /></template>

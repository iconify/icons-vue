<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncy1prbdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ncy1prbdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:caret-right-outlined" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um5hbmb3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="um5hbmb3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:mail-fill" /></template>

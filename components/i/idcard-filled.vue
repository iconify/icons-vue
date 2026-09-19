<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7r5e0e4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="r7r5e0e4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:idcard-filled" /></template>

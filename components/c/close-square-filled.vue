<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kordntbqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="kordntbqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:close-square-filled" /></template>

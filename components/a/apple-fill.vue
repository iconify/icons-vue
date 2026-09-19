<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qi8skqb1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qi8skqb1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:apple-fill" /></template>

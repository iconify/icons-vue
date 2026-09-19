<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd9kdwhel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hd9kdwhel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:left-square-filled" /></template>

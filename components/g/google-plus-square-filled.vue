<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2ze9wbxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="a2ze9wbxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:google-plus-square-filled" /></template>

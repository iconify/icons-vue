<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yto-bccos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="yto-bccos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:like-filled" /></template>

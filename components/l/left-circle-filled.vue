<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a929an8zc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="a929an8zc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:left-circle-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwc9mxbxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vwc9mxbxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:dropbox-circle-filled" /></template>

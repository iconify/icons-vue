<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ll22o1baf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ll22o1baf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:alipay-circle-filled" /></template>

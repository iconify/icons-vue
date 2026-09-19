<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_mv1bd4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="l_mv1bd4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:alipay-square-fill" /></template>

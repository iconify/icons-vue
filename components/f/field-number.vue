<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp-_rmb2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cp-_rmb2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:field-number" /></template>

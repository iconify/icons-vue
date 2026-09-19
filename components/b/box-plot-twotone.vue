<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2l-sc8wc.css';
import '../../css/h/hrlvobb8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="i2l-sc8wc"/><path class="hrlvobb8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:box-plot-twotone" /></template>

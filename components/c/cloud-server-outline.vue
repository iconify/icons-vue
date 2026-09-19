<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-89fbcca.css';
import '../../css/e/eg3hw6b_q.css';
import '../../css/d/d3bu2f_4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="r-89fbcca"/><path class="eg3hw6b_q"/><path class="d3bu2f_4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:cloud-server-outline" /></template>

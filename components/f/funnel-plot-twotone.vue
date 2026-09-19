<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zacvbf9rr.css';
import '../../css/b/bex3sxi3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="zacvbf9rr"/><path class="bex3sxi3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:funnel-plot-twotone" /></template>

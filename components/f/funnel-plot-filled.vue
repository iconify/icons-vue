<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4xf2acrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="a4xf2acrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:funnel-plot-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4fyvha9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="a4fyvha9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:dot-chart" /></template>

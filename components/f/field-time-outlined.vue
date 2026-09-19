<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcb3-fmrh.css';
import '../../css/w/w74cijboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bcb3-fmrh"/><path class="w74cijboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:field-time-outlined" /></template>

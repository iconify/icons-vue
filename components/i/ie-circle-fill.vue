<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdcff_hzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wdcff_hzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:ie-circle-fill" /></template>

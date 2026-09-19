<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ooj2r_z4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ooj2r_z4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:caret-left-outlined" /></template>

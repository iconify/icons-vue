<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmqiz0x_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rmqiz0x_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:dot-net-outlined" /></template>

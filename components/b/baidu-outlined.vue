<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sw9wzvb0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="sw9wzvb0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:baidu-outlined" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tndf3ybwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tndf3ybwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:lock-outline" /></template>

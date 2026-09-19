<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly_u-9biw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ly_u-9biw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:hdd-filled" /></template>

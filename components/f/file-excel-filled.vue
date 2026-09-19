<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vf52asb6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vf52asb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:file-excel-filled" /></template>

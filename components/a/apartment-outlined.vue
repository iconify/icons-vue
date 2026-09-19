<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd4pmb2eb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dd4pmb2eb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:apartment-outlined" /></template>

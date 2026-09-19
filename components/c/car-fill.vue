<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8_6k_bkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="d8_6k_bkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:car-fill" /></template>

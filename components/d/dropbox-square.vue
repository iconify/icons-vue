<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ek4_hnsal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ek4_hnsal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:dropbox-square" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0p4c2bpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="c0p4c2bpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:fund-filled" /></template>

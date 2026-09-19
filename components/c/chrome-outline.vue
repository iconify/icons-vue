<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptc2ntoas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ptc2ntoas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:chrome-outline" /></template>

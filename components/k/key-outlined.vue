<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2kapd5nn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="p2kapd5nn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:key-outlined" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gik1z9cpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gik1z9cpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:ellipsis-outline" /></template>

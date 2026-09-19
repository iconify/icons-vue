<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slae-8e5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="slae-8e5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:eye-fill" /></template>

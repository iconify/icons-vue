<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g596w6bde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="g596w6bde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:insert-row-above" /></template>

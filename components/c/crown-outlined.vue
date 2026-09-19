<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0ns52iae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="y0ns52iae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:crown-outlined" /></template>

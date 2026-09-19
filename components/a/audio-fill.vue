<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_s0f7s9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="u_s0f7s9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:audio-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf0xsld2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wf0xsld2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:logout-outlined" /></template>

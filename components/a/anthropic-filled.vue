<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yln92w6ab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="yln92w6ab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:anthropic-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elmx5rbsv.css';
import '../../css/w/w893w9fet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="elmx5rbsv"/><path class="w893w9fet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:cloud-upload-outline" /></template>

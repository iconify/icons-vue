<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1b1abbxl.css';
import '../../css/e/eoz47dboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="j1b1abbxl"/><path class="eoz47dboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:bell-twotone" /></template>

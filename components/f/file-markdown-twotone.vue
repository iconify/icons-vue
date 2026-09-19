<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6v0htbfx.css';
import '../../css/j/jso3jy2en.css';
import '../../css/e/eca5gmkyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="d6v0htbfx"/><path class="jso3jy2en"/><path class="eca5gmkyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:file-markdown-twotone" /></template>

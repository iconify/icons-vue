<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f85yefe1j.css';
import '../../css/j/jso3jy2en.css';
import '../../css/r/r45tgcbqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="f85yefe1j"/><path class="jso3jy2en"/><path class="r45tgcbqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:file-excel-twotone" /></template>

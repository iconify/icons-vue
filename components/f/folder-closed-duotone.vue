<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/y7rf6wbpp.css';
import '../../css/z/zw73vj3qq.css';
import '../../css/z/zg1pvabjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="y7rf6wbpp"/><path class="zw73vj3qq"/><path class="zg1pvabjx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:folder-closed-duotone" /></template>

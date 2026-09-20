<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vupozobcn.css';
import '../../css/z/zhuxdlbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vupozobcn"/><path class="zhuxdlbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:folder-remove" /></template>

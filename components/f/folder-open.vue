<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yoayjgb4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yoayjgb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:folder-open" /></template>

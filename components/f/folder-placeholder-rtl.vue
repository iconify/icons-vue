<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2kq5nbez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t2kq5nbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:folder-placeholder-rtl" /></template>

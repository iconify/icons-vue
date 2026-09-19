<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za5ojpbbz.css';
import '../../css/t/tdrcj_yxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="za5ojpbbz"/><path class="tdrcj_yxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:data-table" /></template>

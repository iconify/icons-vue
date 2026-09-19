<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/no_04pbeo.css';
import '../../css/z/zw41ydges.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="no_04pbeo"/><path class="zw41ydges"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:inspection" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzik92bzc.css';
import '../../css/q/qstt88dql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="lzik92bzc"/><path class="qstt88dql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-mammography" /></template>

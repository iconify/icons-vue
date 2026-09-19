<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxnh_641e.css';
import '../../css/t/tiggjjbxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hxnh_641e"/><path class="tiggjjbxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-db2-warehouse" /></template>

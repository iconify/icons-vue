<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pshpb9b-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pshpb9b-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:file-search-outlined" /></template>

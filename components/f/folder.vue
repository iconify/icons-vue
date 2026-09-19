<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg2qp55av.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="yg2qp55av"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:folder" /></template>

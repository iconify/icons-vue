<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ol2x7rbre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ol2x7rbre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:folder-add-outlined" /></template>

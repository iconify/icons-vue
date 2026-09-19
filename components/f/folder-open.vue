<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha2zxrbxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ha2zxrbxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:folder-open" /></template>

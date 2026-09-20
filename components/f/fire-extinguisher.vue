<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxf74wbaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxf74wbaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:fire-extinguisher" /></template>

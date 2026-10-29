<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pydbwxl_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pydbwxl_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:file-plus-corner" /></template>

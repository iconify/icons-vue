<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylt94hh4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ylt94hh4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-excel-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/puo_-obzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":473,"height":512};
const content = `<path class="puo_-obzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:fortran" /></template>

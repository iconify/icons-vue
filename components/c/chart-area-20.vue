<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yajgwt04s.css';
import '../../css/r/rblthnbeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yajgwt04s"/><path class="rblthnbeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-area-20" /></template>

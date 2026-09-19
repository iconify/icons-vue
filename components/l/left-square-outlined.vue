<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e032rcl9j.css';
import '../../css/g/gc8-4tb2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="e032rcl9j"/><path class="gc8-4tb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:left-square-outlined" /></template>

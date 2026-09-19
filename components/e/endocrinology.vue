<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yql84dbid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="yql84dbid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:endocrinology" /></template>

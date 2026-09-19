<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyi6f9bda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="uyi6f9bda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:file-sync-outline" /></template>

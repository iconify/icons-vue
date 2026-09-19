<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xskxbdctj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1792};
const content = `<path class="xskxbdctj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:file-excel-o" /></template>

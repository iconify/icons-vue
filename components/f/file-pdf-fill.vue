<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8-hdbbsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="q8-hdbbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:file-pdf-fill" /></template>

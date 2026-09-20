<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9piq1wjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9piq1wjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-excel-box-outline" /></template>

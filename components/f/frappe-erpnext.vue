<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntug3ea9g.css';
import '../../css/y/y6g7tfbrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ntug3ea9g"/><path class="y6g7tfbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:frappe-erpnext" /></template>

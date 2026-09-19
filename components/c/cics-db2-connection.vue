<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxcr60a4i.css';
import '../../css/b/b15_3b_bo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gxcr60a4i"/><path class="b15_3b_bo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cics-db2-connection" /></template>

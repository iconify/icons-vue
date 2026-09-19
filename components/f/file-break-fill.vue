<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syf7txb4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="syf7txb4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:file-break-fill" /></template>

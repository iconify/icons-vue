<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvk8v6b3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gvk8v6b3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:file-earmark-excel-fill" /></template>

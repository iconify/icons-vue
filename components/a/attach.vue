<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4pxh1bsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d4pxh1bsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:attach" /></template>

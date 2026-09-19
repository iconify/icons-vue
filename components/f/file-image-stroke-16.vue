<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idzt2o2kr.css';
import '../../css/p/pmqt2cblr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="idzt2o2kr"/><circle class="pmqt2cblr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:file-image-stroke-16" /></template>

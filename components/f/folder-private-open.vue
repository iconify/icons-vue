<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v702yrfnr.css';
import '../../css/q/qp9anacag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v702yrfnr"/><path class="qp9anacag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-private-open" /></template>

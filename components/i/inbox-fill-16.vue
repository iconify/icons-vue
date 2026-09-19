<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe_qtl4kr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fe_qtl4kr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:inbox-fill-16" /></template>

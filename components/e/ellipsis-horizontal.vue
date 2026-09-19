<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8278_brc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w8278_brc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:ellipsis-horizontal" /></template>

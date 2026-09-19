<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7lop2boe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z7lop2boe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:arrow-double-diagonal" /></template>

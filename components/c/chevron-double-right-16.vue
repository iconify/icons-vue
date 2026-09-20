<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7bd_m0le.css';
import '../../css/d/dg4ly5vpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="a7bd_m0le"/><path clip-rule="evenodd" class="dg4ly5vpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:chevron-double-right-16" /></template>

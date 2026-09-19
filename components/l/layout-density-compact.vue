<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyie12b-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pyie12b-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:layout-density-compact" /></template>

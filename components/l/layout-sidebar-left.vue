<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2j8v34kx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e2j8v34kx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:layout-sidebar-left" /></template>

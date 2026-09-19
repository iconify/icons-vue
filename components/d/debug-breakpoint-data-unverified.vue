<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvnle8i8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uvnle8i8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:debug-breakpoint-data-unverified" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs82pv97p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qs82pv97p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:check-sm-stroke-16" /></template>

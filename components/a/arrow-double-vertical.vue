<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvsuscb2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uvsuscb2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:arrow-double-vertical" /></template>

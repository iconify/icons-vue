<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dn9c1cdua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="dn9c1cdua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:arrowheads-down-right-chevron" /></template>

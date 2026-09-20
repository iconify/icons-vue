<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij-3dl-jv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ij-3dl-jv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:blocked-16" /></template>

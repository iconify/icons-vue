<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbdew6bcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vbdew6bcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:file-csv-outline" /></template>

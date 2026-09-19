<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j33yn6bqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="j33yn6bqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:link" /></template>

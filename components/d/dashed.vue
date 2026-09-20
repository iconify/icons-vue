<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1h3z-d2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="e1h3z-d2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:dashed" /></template>

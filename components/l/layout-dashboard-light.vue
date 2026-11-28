<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds1nbjrev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ds1nbjrev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:layout-dashboard-light" /></template>

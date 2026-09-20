<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug_ngt74t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ug_ngt74t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:elevator" /></template>

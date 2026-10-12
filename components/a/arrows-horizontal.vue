<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijq1e5-qs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijq1e5-qs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:arrows-horizontal" /></template>

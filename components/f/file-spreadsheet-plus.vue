<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ek3vm84wp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ek3vm84wp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:file-spreadsheet-plus" /></template>

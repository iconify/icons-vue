<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd6no_7gl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dd6no_7gl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:apache-parquet" /></template>

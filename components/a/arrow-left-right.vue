<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ag-g8fbxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ag-g8fbxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-left-right" /></template>

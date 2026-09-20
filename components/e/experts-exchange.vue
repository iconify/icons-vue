<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql0ag-0by.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ql0ag-0by"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:experts-exchange" /></template>

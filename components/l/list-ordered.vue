<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erpny4jfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="erpny4jfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:list-ordered" /></template>

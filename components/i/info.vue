<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf4mjdz4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="cf4mjdz4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:info" /></template>

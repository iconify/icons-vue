<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cx362ib6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cx362ib6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:filter" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw32n4xnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="zw32n4xnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:dinner" /></template>

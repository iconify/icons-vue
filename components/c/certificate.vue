<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h87n8dxpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="h87n8dxpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:certificate" /></template>

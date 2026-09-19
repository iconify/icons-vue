<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/po-nq2spx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1856,"height":1408};
const content = `<path class="po-nq2spx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:code" /></template>

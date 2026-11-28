<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-2ck6-qp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-2ck6-qp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:list-filter-x-solid" /></template>

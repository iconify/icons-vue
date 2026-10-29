<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntg47rbey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntg47rbey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:building-solid" /></template>

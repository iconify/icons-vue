<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6f47mbfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6f47mbfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:grid-outline" /></template>

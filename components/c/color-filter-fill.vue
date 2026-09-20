<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oos8e6bxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oos8e6bxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:color-filter-fill" /></template>

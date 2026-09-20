<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt_-b4bfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wt_-b4bfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:filter-2-plus" /></template>

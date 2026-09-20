<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds35rsb-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ds35rsb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:cash-search-bold" /></template>

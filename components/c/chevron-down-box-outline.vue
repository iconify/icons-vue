<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uptpc930r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uptpc930r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chevron-down-box-outline" /></template>

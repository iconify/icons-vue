<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofp1v6byb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofp1v6byb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:filter-2-line" /></template>

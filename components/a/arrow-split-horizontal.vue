<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntdsf7bwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntdsf7bwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-split-horizontal" /></template>

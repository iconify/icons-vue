<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly6e73blf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ly6e73blf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:circle-chevron-down-gloss" /></template>

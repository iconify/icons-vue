<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb_6l7pdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qb_6l7pdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:arrow-circle-right" /></template>

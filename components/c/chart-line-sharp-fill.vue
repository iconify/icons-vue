<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ol24cq_hg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ol24cq_hg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-line-sharp-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sufc7bcoc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sufc7bcoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bar-chart-horizontal-end-fill" /></template>

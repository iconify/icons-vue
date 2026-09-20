<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2u4hqven.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x2u4hqven"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-bar-chart-2-horizontal-end-fill" /></template>

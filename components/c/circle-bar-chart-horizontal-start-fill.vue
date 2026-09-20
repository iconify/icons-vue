<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-6qpzjjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o-6qpzjjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-bar-chart-horizontal-start-fill" /></template>

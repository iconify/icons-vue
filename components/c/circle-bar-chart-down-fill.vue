<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ju_8lzt-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ju_8lzt-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-bar-chart-down-fill" /></template>

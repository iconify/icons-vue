<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vis5bn6ai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vis5bn6ai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:film" /></template>

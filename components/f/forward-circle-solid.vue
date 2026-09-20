<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rg7skrbjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rg7skrbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:forward-circle-solid" /></template>

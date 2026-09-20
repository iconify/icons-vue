<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ns49d_t4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ns49d_t4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:lira-square-solid" /></template>

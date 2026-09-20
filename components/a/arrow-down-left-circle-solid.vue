<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aj-82_nyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aj-82_nyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-down-left-circle-solid" /></template>

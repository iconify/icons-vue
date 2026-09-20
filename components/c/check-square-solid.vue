<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0b3d79qc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u0b3d79qc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:check-square-solid" /></template>

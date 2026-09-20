<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axqt_ft5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axqt_ft5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:laptop-mac" /></template>

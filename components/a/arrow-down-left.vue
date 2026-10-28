<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s99g4i0sv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s99g4i0sv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-down-left" /></template>

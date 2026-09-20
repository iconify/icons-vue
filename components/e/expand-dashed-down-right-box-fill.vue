<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs3b2pbzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vs3b2pbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:expand-dashed-down-right-box-fill" /></template>

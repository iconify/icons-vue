<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdcg-32fy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdcg-32fy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:laugh-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvo3i_ynj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvo3i_ynj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:chart" /></template>

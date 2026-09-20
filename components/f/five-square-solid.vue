<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l70wn9y2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l70wn9y2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:five-square-solid" /></template>

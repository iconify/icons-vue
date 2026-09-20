<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6rs2wg2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6rs2wg2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:clock-hexagon-solid" /></template>

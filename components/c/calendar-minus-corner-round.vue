<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug7e57byd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ug7e57byd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-minus-corner-round" /></template>

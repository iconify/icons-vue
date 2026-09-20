<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8g6wtb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8g6wtb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:brightness-low" /></template>

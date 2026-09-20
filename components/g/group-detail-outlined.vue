<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxjrqc45e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxjrqc45e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:group-detail-outlined" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqc3pmu_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wqc3pmu_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:caret-right-square-filled" /></template>

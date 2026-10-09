<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezhonm73e.css';
import '../../css/v/vck8c0qcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ezhonm73e"/><path class="vck8c0qcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:esg-report-20" /></template>

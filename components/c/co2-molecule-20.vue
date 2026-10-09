<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x64tqdbkh.css';
import '../../css/g/gr4zytbch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x64tqdbkh"/><path class="gr4zytbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:co2-molecule-20" /></template>

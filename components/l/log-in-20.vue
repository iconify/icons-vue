<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbmplvbtr.css';
import '../../css/z/ztnh5ln4w.css';
import '../../css/a/afdw2ab2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sbmplvbtr"/><path class="ztnh5ln4w"/><path class="afdw2ab2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:log-in-20" /></template>

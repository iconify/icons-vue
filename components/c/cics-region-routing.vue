<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w80cq7bag.css';
import '../../css/g/g9n4ckv2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w80cq7bag"/><path class="g9n4ckv2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cics-region-routing" /></template>

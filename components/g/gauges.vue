<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7ocakb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l7ocakb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:gauges" /></template>

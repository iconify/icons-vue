<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iehuhwb2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="iehuhwb2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-outer-light-right-horizontal-stipple" /></template>

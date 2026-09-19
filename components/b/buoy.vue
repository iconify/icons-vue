<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogv16_bqf.css';
import '../../css/d/djjdvpbpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ogv16_bqf"/><path class="djjdvpbpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:buoy" /></template>

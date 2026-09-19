<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uszyinm-l.css';
import '../../css/e/evom4wbsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uszyinm-l"/><path class="evom4wbsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:filter-reset" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnhai55oa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="nnhai55oa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:calculator-percentage" /></template>

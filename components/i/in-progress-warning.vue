<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz_fdacbr.css';
import '../../css/j/jj9znifff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wz_fdacbr"/><path class="jj9znifff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:in-progress-warning" /></template>

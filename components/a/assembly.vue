<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb789wboj.css';
import '../../css/t/t79m5jbmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bb789wboj"/><path class="t79m5jbmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:assembly" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbdwj-b8d.css';
import '../../css/c/czh-er49n.css';
import '../../css/n/n78tmpqhz.css';
import '../../css/e/e39ud6bwf.css';
import '../../css/j/jiw373bod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tbdwj-b8d"/><circle class="czh-er49n"/><circle class="n78tmpqhz"/><circle class="e39ud6bwf"/><path class="jiw373bod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-watsonx-orchestrate" /></template>

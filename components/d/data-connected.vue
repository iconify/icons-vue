<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc8783bec.css';
import '../../css/q/qmao7mx0z.css';
import '../../css/q/qjaiieb6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nc8783bec"/><path class="qmao7mx0z"/><path class="qjaiieb6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:data-connected" /></template>

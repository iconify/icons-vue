<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/r/rml6syxed.css';
import '../../css/p/pv0dl6bjc.css';
import '../../css/r/rrbbmlbwz.css';
import '../../css/u/un6xfgbrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="bi12bsetm"><circle class="rml6syxed"/><path class="pv0dl6bjc"/><path class="rrbbmlbwz"/><path class="un6xfgbrp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency-color:arnx" /></template>

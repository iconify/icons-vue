<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvradzqdb.css';
import '../../css/y/yvl9v5b9e.css';
import '../../css/p/psjdr85ae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cvradzqdb"/><path class="yvl9v5b9e"/><path class="psjdr85ae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:async" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owmm25bsk.css';
import '../../css/v/v8sc8rzsp.css';
import '../../css/m/meey0ablw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="owmm25bsk"/><path class="v8sc8rzsp"/><path class="meey0ablw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:cursor" /></template>

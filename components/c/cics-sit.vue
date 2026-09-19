<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpje9lbhk.css';
import '../../css/r/rkrmrebfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zpje9lbhk"/><path class="rkrmrebfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cics-sit" /></template>

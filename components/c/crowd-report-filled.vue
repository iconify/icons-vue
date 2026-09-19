<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ws9aemb-h.css';
import '../../css/m/mkjrunb1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ws9aemb-h"/><path class="mkjrunb1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:crowd-report-filled" /></template>

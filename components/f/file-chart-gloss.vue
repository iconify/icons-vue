<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/op3-_109a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="op3-_109a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-chart-gloss" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq6yr4kct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="eq6yr4kct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:doc-chart" /></template>

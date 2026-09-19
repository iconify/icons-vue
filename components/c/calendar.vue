<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rokj4hbjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1664};
const content = `<path class="rokj4hbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:calendar" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c55vgcbjc.css';
import '../../css/n/n-obmabwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c55vgcbjc"/><path class="n-obmabwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:in-progress-error" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t01b7nbne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="t01b7nbne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:lane-divide-three" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h855_yb2w.css';
import '../../css/v/vlrrqacry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="h855_yb2w"/><path class="vlrrqacry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:conditional-flow" /></template>

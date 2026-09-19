<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvhew3bau.css';
import '../../css/t/tb-x70blq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jvhew3bau"/><path class="tb-x70blq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ai-launch" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsc-4-bas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jsc-4-bas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:footwear-decontamination" /></template>

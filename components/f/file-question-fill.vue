<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltq6thbqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ltq6thbqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:file-question-fill" /></template>

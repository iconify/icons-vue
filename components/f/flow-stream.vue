<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nuwikiitw.css';
import '../../css/f/f7t-e2bsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nuwikiitw"/><path class="f7t-e2bsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:flow-stream" /></template>

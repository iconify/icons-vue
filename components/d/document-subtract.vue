<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utg4a_brp.css';
import '../../css/o/o104vdwci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="utg4a_brp"/><path class="o104vdwci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:document-subtract" /></template>

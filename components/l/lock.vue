<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9t5qgbnj.css';
import '../../css/u/uqsh6ibhf.css';
import '../../css/p/pr87757ke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x9t5qgbnj"/><path class="uqsh6ibhf"/><circle class="pr87757ke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:lock" /></template>

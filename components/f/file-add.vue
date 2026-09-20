<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clfpmnbkh.css';
import '../../css/d/dag1i075l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="clfpmnbkh"/><path class="dag1i075l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:file-add" /></template>

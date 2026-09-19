<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf97cqb0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2000,"height":2000};
const content = `<path class="pf97cqb0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:compensation-marker" /></template>

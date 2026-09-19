<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw1ho0t9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fw1ho0t9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:bpmn-escalation-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdb5gbc-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fdb5gbc-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:bpmn-conditional-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8ojk_b7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v8ojk_b7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:bpmn-link-outline" /></template>

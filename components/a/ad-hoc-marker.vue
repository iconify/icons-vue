<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck_742b9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2000,"height":2000};
const content = `<path class="ck_742b9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:ad-hoc-marker" /></template>

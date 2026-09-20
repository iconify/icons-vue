<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q953-nbum.css';
import '../../css/u/u9-d979uw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ouiIcon__fillSecondary q953-nbum"/><path class="u9-d979uw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:app-sql" /></template>

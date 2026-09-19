<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvhy-ba_m.css';
import '../../css/n/n7pqid28s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hvhy-ba_m"/><path class="n7pqid28s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:generate-pdf" /></template>

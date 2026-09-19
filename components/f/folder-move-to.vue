<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/li9q4lu4g.css';
import '../../css/r/rvbsrrkcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="li9q4lu4g"/><path class="rvbsrrkcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:folder-move-to" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okiwfbt0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="okiwfbt0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-match-360" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb_lofoyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kb_lofoyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:elastic-search" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsnta9bsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qsnta9bsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ai-enabled-pdlc" /></template>

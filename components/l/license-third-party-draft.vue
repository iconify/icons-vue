<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sy-hsnmqc.css';
import '../../css/f/f1ijkjbnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sy-hsnmqc"/><path class="f1ijkjbnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:license-third-party-draft" /></template>

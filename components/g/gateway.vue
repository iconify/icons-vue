<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac1ym9b_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<rect transform="rotate(-45 -120466.552 -49977.13)scale(96.7529)" class="ac1ym9b_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:gateway" /></template>

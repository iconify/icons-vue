<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqa4lnbka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="lqa4lnbka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:intermediate-event-throw-message" /></template>

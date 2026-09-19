<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfwtfdz8c.css';
import '../../css/r/rzh_o5duh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2000,"height":2000};
const content = `<path class="bfwtfdz8c"/><path class="rzh_o5duh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:business-rule" /></template>

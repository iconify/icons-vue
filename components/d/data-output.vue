<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmierzc3a.css';
import '../../css/t/t3qjwd-yy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2000,"height":2000};
const content = `<path class="lmierzc3a"/><path class="t3qjwd-yy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:data-output" /></template>

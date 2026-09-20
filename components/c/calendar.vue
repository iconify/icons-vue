<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-zwmgb6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q-zwmgb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:calendar" /></template>

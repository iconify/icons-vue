<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1i1mgbez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t1i1mgbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:inbox-double" /></template>

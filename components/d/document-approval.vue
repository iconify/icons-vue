<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu2grvbsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="vu2grvbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:document-approval" /></template>

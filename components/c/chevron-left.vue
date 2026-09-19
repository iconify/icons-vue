<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr6jxknlm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gr6jxknlm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:chevron-left" /></template>

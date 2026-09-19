<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkr04ob9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rkr04ob9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:copy" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsx4-tbes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dsx4-tbes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:kql-operand" /></template>

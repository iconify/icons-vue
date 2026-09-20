<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgsr__boq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hgsr__boq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:lift-gate-lowered" /></template>

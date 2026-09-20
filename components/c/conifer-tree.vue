<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-2s0cbsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="e-2s0cbsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:conifer-tree" /></template>

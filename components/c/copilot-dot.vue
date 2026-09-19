<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_k0mzjpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x_k0mzjpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:copilot-dot" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-ako4bre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="k-ako4bre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:copilot-blocked" /></template>

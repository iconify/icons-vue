<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgnn4eb5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qgnn4eb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:dependabot" /></template>

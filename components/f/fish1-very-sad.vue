<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0wc70byl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s0wc70byl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:fish1-very-sad" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9y6d-b5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w9y6d-b5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:bracket-error" /></template>

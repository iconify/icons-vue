<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klr151b3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="klr151b3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:arrow-down-16" /></template>

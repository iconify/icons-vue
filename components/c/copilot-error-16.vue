<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpcee99wy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cpcee99wy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:copilot-error-16" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nte0_mbcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nte0_mbcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:arrow-circle-up-sparkle" /></template>

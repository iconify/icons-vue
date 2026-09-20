<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vubic6b0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vubic6b0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:horizontal-rule-16" /></template>

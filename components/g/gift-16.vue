<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbs78_90o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rbs78_90o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:gift-16" /></template>

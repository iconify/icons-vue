<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_e3j9oms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y_e3j9oms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:arrow-down-left-16" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/on1r8lbod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="on1r8lbod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:credit-card" /></template>

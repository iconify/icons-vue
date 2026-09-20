<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjopbq_ry.css';
import '../../css/r/rrbhc-fdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kjopbq_ry"/><path class="rrbhc-fdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:dependabot-16" /></template>

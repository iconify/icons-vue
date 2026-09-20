<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whcnm8bom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="whcnm8bom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:diff-removed-16" /></template>

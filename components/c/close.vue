<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvfs0_xvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pvfs0_xvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:close" /></template>

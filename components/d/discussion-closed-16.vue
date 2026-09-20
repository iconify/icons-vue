<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k74075dxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k74075dxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:discussion-closed-16" /></template>

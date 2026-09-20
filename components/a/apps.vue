<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sam1kjbyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sam1kjbyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:apps" /></template>

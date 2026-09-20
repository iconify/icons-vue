<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ge0zdlm-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ge0zdlm-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:health-microscope" /></template>

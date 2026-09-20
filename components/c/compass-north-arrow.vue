<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwbdq-bvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="bwbdq-bvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:compass-north-arrow" /></template>

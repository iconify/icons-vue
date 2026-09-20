<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oa2ueoszy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="oa2ueoszy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-horizontal-up-stipple-down" /></template>

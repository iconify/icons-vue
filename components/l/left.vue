<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4g2mfism.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":208,"height":448};
const content = `<path class="e4g2mfism"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:left" /></template>

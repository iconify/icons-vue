<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvezambly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uvezambly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:9-circle-fill" /></template>

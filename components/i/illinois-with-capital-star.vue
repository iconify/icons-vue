<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbf2a2b4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jbf2a2b4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:illinois-with-capital-star" /></template>

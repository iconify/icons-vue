<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8befvb3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c8befvb3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bag-with-greek-cross" /></template>

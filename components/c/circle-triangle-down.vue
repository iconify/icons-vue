<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctuk4ds0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="ctuk4ds0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:circle-triangle-down" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrjoz9gfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jrjoz9gfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:heart-with-ecg-line" /></template>

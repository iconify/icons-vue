<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxomwi7cb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="pxomwi7cb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:closed-caption" /></template>

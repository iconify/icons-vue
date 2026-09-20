<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/on0myty0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="on0myty0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:link" /></template>

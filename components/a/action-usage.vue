<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ad_rmyb6z.css';
import '../../css/f/f-7sbkbnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ad_rmyb6z"/><path class="f-7sbkbnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:action-usage" /></template>

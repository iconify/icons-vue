<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dl20pggri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dl20pggri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:arrowleft" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehj399b5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ehj399b5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:biohazard" /></template>

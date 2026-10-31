<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1u-ccs4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1u-ccs4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-compare-fill-round" /></template>

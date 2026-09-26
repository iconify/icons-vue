<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aum5-lbpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aum5-lbpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:content-navigator-edit-service-upload" /></template>

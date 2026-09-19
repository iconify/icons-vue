<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjeb2y1lr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yjeb2y1lr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:android" /></template>

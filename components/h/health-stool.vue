<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4b-ycgux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d4b-ycgux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:health-stool" /></template>

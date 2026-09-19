<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8458j73b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e8458j73b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-arrow-dropup-circle" /></template>

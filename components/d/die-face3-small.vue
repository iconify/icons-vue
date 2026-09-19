<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbs6tsbhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="cbs6tsbhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:die-face3-small" /></template>

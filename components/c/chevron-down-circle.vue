<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgkg3lb2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dgkg3lb2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:chevron-down-circle" /></template>

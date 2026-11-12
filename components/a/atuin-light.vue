<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5q_pxnmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e5q_pxnmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:atuin-light" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fifbmgb2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fifbmgb2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:grav" /></template>

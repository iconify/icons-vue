<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu8j9_fgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xu8j9_fgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:jinear-dark" /></template>

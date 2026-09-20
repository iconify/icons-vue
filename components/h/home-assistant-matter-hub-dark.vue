<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/no6vjtbbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="no6vjtbbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:home-assistant-matter-hub-dark" /></template>

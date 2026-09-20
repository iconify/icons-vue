<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fy7_nzbds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fy7_nzbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:loops-dark" /></template>

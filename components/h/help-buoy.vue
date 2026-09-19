<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrm63qbac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nrm63qbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:help-buoy" /></template>

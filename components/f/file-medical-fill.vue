<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsvaxh48l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rsvaxh48l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:file-medical-fill" /></template>

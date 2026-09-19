<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzklnnopo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="tzklnnopo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:briefcase-medical-bold" /></template>

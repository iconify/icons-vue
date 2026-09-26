<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ou9mpkptl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ou9mpkptl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:content-navigator-edit-service-download" /></template>

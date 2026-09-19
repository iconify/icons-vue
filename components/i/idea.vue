<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdxce3pve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vdxce3pve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:idea" /></template>

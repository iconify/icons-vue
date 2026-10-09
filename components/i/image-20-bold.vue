<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i48le1b7u.css';
import '../../css/o/ofb0s2_ou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i48le1b7u"/><path class="ofb0s2_ou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:image-20-bold" /></template>

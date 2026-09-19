<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhaitq0ho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nhaitq0ho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:adobe-aftereffects" /></template>

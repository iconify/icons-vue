<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi7vgif3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yi7vgif3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:basketball-stroke-16" /></template>

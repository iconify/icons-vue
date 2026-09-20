<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp1kyrs5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fp1kyrs5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:freecad-dark" /></template>

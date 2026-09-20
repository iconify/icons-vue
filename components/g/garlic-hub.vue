<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu0ij6bnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fu0ij6bnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:garlic-hub" /></template>

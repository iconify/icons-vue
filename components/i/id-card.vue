<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5p2s1bwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u5p2s1bwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:id-card" /></template>

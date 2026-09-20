<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5uozyb2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f5uozyb2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:apple-music-light" /></template>

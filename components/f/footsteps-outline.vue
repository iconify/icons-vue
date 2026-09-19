<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_jb2p2jd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y_jb2p2jd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:footsteps-outline" /></template>

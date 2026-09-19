<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydl97abvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ydl97abvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:bomb" /></template>

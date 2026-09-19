<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cizxf3pgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cizxf3pgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:crystal" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyx366rwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hyx366rwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:file-jpg-outline" /></template>

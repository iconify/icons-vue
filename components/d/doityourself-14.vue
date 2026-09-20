<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u34x-cb8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="u34x-cb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:doityourself-14" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3v4-kb9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m3v4-kb9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:gg" /></template>

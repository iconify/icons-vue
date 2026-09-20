<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trmo9wb3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="trmo9wb3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:drafting-compass" /></template>

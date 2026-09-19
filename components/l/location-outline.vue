<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2_4izbfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="k2_4izbfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:location-outline" /></template>

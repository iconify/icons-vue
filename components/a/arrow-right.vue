<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crv2btj3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="crv2btj3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:arrow-right" /></template>

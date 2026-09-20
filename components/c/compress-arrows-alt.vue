<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4m3nlfkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i4m3nlfkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:compress-arrows-alt" /></template>

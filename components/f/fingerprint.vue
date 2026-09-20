<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p75amib7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p75amib7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:fingerprint" /></template>

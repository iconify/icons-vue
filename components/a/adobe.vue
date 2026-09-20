<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9wld51md.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i9wld51md"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:adobe" /></template>

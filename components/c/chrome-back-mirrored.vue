<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ap8hstwxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ap8hstwxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:chrome-back-mirrored" /></template>

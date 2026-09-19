<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2so2abal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u2so2abal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-calendar" /></template>

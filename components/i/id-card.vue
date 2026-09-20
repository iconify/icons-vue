<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/roek0__-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="roek0__-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:id-card" /></template>

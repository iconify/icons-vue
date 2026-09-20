<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7gb1fb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i7gb1fb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:binoculars" /></template>

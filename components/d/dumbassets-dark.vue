<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwog5qh3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mwog5qh3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dumbassets-dark" /></template>

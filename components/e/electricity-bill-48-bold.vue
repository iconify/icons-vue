<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk4s-jblr.css';
import '../../css/c/c7rnb2klb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qk4s-jblr"/><path class="c7rnb2klb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:electricity-bill-48-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4_iznb1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q4_iznb1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:grav" /></template>

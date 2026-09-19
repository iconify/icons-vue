<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7ev_gi8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="q7ev_gi8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:at" /></template>

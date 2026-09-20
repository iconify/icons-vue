<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgl83sa6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rgl83sa6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:fingerprint-outline" /></template>

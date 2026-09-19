<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4w3hi4pl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="k4w3hi4pl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:i-o-s-app-store-logo" /></template>

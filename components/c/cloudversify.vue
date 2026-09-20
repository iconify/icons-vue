<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/keak4mbei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="keak4mbei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:cloudversify" /></template>

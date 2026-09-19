<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_jhyxxgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z_jhyxxgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:bathtub" /></template>
